<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7atsbiux.css';
import '../../css/y/yakywwbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d7atsbiux"/><path class="yakywwbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-box-double-stroke-20" {...props}></Icon>
