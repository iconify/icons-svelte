<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utr3r6_dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utr3r6_dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:reply-24" {...props}></Icon>
