<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_0n_vbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e_0n_vbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:euro-solid" {...props}></Icon>
