<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_lmzkbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="z_lmzkbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:5g" {...props}></Icon>
