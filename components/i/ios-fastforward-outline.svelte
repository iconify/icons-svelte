<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrl1jkw7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zrl1jkw7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-fastforward-outline" {...props}></Icon>
