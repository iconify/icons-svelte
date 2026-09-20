<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anr0_ixlq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anr0_ixlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:money-bill" {...props}></Icon>
