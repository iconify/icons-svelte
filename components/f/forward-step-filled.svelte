<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0pkl8b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0pkl8b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:forward-step-filled" {...props}></Icon>
