<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/matp353vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="matp353vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:math-symbols-solid" {...props}></Icon>
