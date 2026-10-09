<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_reqgbqv.css';
import '../../css/l/la3dn2r7d.css';
import '../../css/u/ubtst-b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n_reqgbqv"/><path class="la3dn2r7d"/><path class="ubtst-b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jerrycan-20" {...props}></Icon>
