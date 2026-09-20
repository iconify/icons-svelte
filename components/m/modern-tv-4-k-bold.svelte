<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq50w1k7n.css';
import '../../css/k/ki6y78brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq50w1k7n"/><path class="ki6y78brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:modern-tv-4-k-bold" {...props}></Icon>
