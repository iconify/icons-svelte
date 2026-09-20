<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t01iarbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t01iarbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:padlock-square-2" {...props}></Icon>
