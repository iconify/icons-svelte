<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj0ye9czm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj0ye9czm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:remove-from-cart" {...props}></Icon>
