<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd9zdhbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd9zdhbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-printables" {...props}></Icon>
