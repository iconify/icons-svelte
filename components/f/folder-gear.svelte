<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_rm2k5zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_rm2k5zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folder-gear" {...props}></Icon>
