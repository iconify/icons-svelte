<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbft5sbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbft5sbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:input" {...props}></Icon>
