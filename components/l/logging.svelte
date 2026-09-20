<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw-wtubas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yw-wtubas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:logging" {...props}></Icon>
