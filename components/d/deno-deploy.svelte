<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf_adyava.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf_adyava"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deno-deploy" {...props}></Icon>
