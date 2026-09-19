<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jily80biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jily80biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:network-topology" {...props}></Icon>
