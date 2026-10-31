<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-qr-tb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-qr-tb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-left-small-fill-round" {...props}></Icon>
