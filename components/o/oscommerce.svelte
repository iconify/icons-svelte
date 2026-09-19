<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdvgp638f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="gdvgp638f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:oscommerce" {...props}></Icon>
