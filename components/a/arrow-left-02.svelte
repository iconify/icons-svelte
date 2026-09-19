<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kif8d7ioj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kif8d7ioj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-left-02" {...props}></Icon>
