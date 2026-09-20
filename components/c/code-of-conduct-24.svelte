<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifftp-7_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifftp-7_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:code-of-conduct-24" {...props}></Icon>
