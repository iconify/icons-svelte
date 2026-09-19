<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpo_93sap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xpo_93sap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:keyboard-tab" {...props}></Icon>
