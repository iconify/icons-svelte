<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-b_krv-u.css';
import '../../css/z/zs61z1u9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-b_krv-u"/><path class="zs61z1u9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:indent-increase-line" {...props}></Icon>
