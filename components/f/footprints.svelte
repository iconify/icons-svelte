<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0_pr_bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0_pr_bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:footprints" {...props}></Icon>
