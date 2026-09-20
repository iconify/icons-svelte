<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-y74lb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-y74lb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:chart-area-outline" {...props}></Icon>
