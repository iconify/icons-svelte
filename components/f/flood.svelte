<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st_hwob4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st_hwob4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:flood" {...props}></Icon>
