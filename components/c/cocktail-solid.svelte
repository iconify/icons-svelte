<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo-cg4aud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lo-cg4aud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cocktail-solid" {...props}></Icon>
