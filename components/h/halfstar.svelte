<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-hlav_un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":961};
const content = `<path class="v-hlav_un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:halfstar" {...props}></Icon>
