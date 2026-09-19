<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0msh_vzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":833,"height":1024};
const content = `<path class="m0msh_vzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:manillaenvelope" {...props}></Icon>
