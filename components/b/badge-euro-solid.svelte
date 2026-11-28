<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzlhxm12g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzlhxm12g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-euro-solid" {...props}></Icon>
