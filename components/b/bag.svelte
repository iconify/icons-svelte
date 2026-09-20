<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3jslumyd.css';
import '../../css/t/tzc9byxdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3jslumyd"/><path class="tzc9byxdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:bag" {...props}></Icon>
