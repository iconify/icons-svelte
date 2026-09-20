<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8-ciublm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8-ciublm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fast-forward-30" {...props}></Icon>
