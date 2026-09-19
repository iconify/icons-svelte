<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrmr0yb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrmr0yb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:physical-therapy" {...props}></Icon>
