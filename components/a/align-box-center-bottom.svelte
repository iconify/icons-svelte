<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxb_lrbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxb_lrbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-center-bottom" {...props}></Icon>
