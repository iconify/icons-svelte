<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt17-0bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zt17-0bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-plus-duotone" {...props}></Icon>
