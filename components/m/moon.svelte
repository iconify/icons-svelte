<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsjj_hvfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsjj_hvfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:moon" {...props}></Icon>
