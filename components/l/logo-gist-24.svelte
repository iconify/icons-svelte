<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueozdva-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":38,"height":24};
const content = `<path class="ueozdva-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:logo-gist-24" {...props}></Icon>
