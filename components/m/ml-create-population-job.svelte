<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzorb_z0w.css';
import '../../css/s/slpzz11by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rzorb_z0w"/><path class="ouiIcon__fillSecondary slpzz11by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:ml-create-population-job" {...props}></Icon>
