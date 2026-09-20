<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5t4qho-n.css';
import '../../css/e/e3e-l4bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j5t4qho-n ouiIcon__fillSecondary"/><path class="e3e-l4bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-management" {...props}></Icon>
