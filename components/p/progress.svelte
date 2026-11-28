<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljov1rb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljov1rb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:progress" {...props}></Icon>
