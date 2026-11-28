<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfvbl4bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfvbl4bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-cog-solid" {...props}></Icon>
