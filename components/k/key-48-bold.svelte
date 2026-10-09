<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umhq261qv.css';
import '../../css/g/gf_wrnomr.css';
import '../../css/p/p5jrx9s3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="umhq261qv"/><path class="gf_wrnomr"/><path class="p5jrx9s3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:key-48-bold" {...props}></Icon>
