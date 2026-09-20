<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnws3owxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jnws3owxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:react-wheel-picker-light" {...props}></Icon>
