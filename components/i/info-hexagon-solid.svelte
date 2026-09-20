<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt0p3obti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt0p3obti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:info-hexagon-solid" {...props}></Icon>
