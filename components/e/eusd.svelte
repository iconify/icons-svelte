<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e35k8uvkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e35k8uvkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:eusd" {...props}></Icon>
