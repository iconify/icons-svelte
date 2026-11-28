<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ced2b_b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ced2b_b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folder-minus" {...props}></Icon>
