<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltkf0bsxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltkf0bsxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:apps-box" {...props}></Icon>
