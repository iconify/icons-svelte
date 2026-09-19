<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e__0vq20f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e__0vq20f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:download" {...props}></Icon>
