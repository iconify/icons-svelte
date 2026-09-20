<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjrs50btb.css';
import '../../css/c/cig9b4c-v.css';
import '../../css/z/zp7f7h2us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mjrs50btb"/><path class="cig9b4c-v"/><path class="zp7f7h2us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:beauty-barber-light-sign" {...props}></Icon>
