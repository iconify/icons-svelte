<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr8u1glpl.css';
import '../../css/h/h4erxx0-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr8u1glpl"/><path class="h4erxx0-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-algolia" {...props}></Icon>
