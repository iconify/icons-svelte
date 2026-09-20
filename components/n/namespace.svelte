<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mec5up-yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mec5up-yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:namespace" {...props}></Icon>
