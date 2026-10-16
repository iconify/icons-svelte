<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyc_-lbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":600,"height":600};
const content = `<path class="lyc_-lbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:organizr" {...props}></Icon>
