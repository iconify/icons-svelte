<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj06nrhcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj06nrhcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:open-containers-initiative" {...props}></Icon>
