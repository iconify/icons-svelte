<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc1rx7bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc1rx7bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-js" {...props}></Icon>
