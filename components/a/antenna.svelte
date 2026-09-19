<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn1j3bxoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn1j3bxoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:antenna" {...props}></Icon>
