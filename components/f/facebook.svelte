<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghy45sw0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghy45sw0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:facebook" {...props}></Icon>
