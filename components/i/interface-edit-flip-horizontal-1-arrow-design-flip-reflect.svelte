<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr3h8eklo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cr3h8eklo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-flip-horizontal-1-arrow-design-flip-reflect" {...props}></Icon>
