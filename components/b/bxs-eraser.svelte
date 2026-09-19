<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf4wk1bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf4wk1bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-eraser" {...props}></Icon>
