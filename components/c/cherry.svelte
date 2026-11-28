<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-pbe_bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-pbe_bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cherry" {...props}></Icon>
