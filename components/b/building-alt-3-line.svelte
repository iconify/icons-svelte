<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmhlr2brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmhlr2brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:building-alt-3-line" {...props}></Icon>
