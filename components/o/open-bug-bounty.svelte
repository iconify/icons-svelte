<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxyvf0bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxyvf0bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:open-bug-bounty" {...props}></Icon>
