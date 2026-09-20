<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8220sveq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n8220sveq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:allergens-fish-solid" {...props}></Icon>
