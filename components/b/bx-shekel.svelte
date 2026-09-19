<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmc2g5_rg.css';
import '../../css/s/s5ck4pbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmc2g5_rg"/><path class="s5ck4pbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-shekel" {...props}></Icon>
