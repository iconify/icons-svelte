<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l67lj9z9h.css';
import '../../css/e/eucgmebad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l67lj9z9h"/><path class="eucgmebad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-ring-1-filled" {...props}></Icon>
