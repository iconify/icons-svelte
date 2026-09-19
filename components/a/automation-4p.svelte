<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1bxfbbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="f1bxfbbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:automation-4p" {...props}></Icon>
