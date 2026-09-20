<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfd1aptvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rfd1aptvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:mercedes" {...props}></Icon>
