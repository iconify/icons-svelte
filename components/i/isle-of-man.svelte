<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_-t-h0ew.css';
import '../../css/f/fxrygx0ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="k_-t-h0ew"/><path class="fxrygx0ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:isle-of-man" {...props}></Icon>
