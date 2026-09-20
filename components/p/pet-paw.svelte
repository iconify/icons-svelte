<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2i2aodww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="k2i2aodww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pet-paw" {...props}></Icon>
