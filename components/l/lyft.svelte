<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7xcoth-m.css';
import '../../css/x/x-5p19nze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7xcoth-m"/><path class="x-5p19nze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:lyft" {...props}></Icon>
