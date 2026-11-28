<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zesyah_yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zesyah_yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:code-play" {...props}></Icon>
