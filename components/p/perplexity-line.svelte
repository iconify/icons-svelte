<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm2x4mzsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm2x4mzsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:perplexity-line" {...props}></Icon>
