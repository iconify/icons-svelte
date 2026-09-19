<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoulf5bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zoulf5bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-alipay" {...props}></Icon>
