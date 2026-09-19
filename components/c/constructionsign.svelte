<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw9fgdciv.css';
import '../../css/f/fcozcbcdu.css';
import '../../css/v/vuax4ju9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dw9fgdciv"/><path class="fcozcbcdu"/><path class="vuax4ju9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:constructionsign" {...props}></Icon>
