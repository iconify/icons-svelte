<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk7gl_bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk7gl_bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:polygon-line" {...props}></Icon>
