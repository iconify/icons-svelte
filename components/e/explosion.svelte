<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s27823v-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s27823v-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:explosion" {...props}></Icon>
