<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj2a8g2fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fj2a8g2fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:check-filled" {...props}></Icon>
