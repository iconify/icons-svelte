<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt2bel8xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt2bel8xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:certificate-star" {...props}></Icon>
