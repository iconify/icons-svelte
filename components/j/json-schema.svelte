<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bznz2_2wt.css';
import '../../css/l/lrr-utbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960,"top":-960};
const content = `<path class="bznz2_2wt"/><path class="lrr-utbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:json-schema" {...props}></Icon>
