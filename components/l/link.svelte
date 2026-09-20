<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luh1hccas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luh1hccas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:link" {...props}></Icon>
