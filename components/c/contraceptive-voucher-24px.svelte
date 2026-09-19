<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5a4ewb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c5a4ewb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:contraceptive-voucher-24px" {...props}></Icon>
