<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za0ygy1bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za0ygy1bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-2x2-x-fill" {...props}></Icon>
