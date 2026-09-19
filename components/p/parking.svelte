<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s015anbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s015anbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:parking" {...props}></Icon>
