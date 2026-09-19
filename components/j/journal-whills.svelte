<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mipg4xb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="mipg4xb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:journal-whills" {...props}></Icon>
