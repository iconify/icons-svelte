<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d14nygiuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d14nygiuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dyson-desk" {...props}></Icon>
