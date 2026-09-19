<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0fml_gub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="k0fml_gub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:phone-alt" {...props}></Icon>
