<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t10d3dbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t10d3dbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:marriott" {...props}></Icon>
