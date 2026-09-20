<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_zup3_vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_zup3_vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:coupon-fill" {...props}></Icon>
