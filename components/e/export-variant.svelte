<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiq64yb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eiq64yb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:export-variant" {...props}></Icon>
