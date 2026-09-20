<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmjt_wemd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmjt_wemd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:life-ring" {...props}></Icon>
