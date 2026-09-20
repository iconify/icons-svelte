<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_vg5qb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_vg5qb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:folder" {...props}></Icon>
