<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdf4m1b4v.css';
import '../../css/e/e3rrscc8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="mdf4m1b4v"/><path class="e3rrscc8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:download" {...props}></Icon>
