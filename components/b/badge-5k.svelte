<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq1ifdc2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq1ifdc2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:badge-5k" {...props}></Icon>
