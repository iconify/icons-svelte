<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cejh-x8ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cejh-x8ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chevrons-right-left-line" {...props}></Icon>
