<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzl802ntq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzl802ntq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-k-hexagon-solid" {...props}></Icon>
