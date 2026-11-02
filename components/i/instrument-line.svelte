<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksp-3cifm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksp-3cifm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:instrument-line" {...props}></Icon>
