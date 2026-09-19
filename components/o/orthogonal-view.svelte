<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-wiaqb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-wiaqb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:orthogonal-view" {...props}></Icon>
