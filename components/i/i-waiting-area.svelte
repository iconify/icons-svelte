<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mas2u-b0z.css';
import '../../css/u/u2y7rxb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="mas2u-b0z"/><path class="u2y7rxb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-waiting-area" {...props}></Icon>
