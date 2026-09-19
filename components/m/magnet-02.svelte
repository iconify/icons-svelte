<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr4hadbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr4hadbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:magnet-02" {...props}></Icon>
