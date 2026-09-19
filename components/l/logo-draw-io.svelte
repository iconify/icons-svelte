<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf2vagbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vf2vagbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-draw-io" {...props}></Icon>
