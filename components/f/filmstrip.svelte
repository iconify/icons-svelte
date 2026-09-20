<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prd4v3_sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prd4v3_sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:filmstrip" {...props}></Icon>
