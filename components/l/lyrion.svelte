<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8c3l2b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8c3l2b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lyrion" {...props}></Icon>
