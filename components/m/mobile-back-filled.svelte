<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp6h30bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp6h30bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mobile-back-filled" {...props}></Icon>
