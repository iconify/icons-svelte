<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg1mfnptg.css';
import '../../css/l/l6wc1bw2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hg1mfnptg"/><path class="l6wc1bw2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:browser-com-bold" {...props}></Icon>
