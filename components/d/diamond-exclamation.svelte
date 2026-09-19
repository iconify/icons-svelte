<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4bs40g2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a4bs40g2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:diamond-exclamation" {...props}></Icon>
