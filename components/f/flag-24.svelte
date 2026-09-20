<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7_mocrpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7_mocrpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:flag-24" {...props}></Icon>
