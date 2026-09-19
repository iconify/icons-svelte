<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1kl_f1gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="k1kl_f1gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:burn-bold" {...props}></Icon>
