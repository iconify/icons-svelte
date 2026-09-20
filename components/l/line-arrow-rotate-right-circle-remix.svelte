<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awjitp7ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="awjitp7ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:line-arrow-rotate-right-circle-remix" {...props}></Icon>
