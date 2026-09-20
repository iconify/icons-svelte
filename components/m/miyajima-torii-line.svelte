<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cse72pblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cse72pblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:miyajima-torii-line" {...props}></Icon>
