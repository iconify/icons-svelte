<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk86tob3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk86tob3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:flag-outline" {...props}></Icon>
