<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf9im3bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf9im3bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-hail" {...props}></Icon>
