<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yji5pzqcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yji5pzqcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:briefcase" {...props}></Icon>
