<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4mmrhd5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4mmrhd5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:images" {...props}></Icon>
