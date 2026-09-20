<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e11cv8b-r.css';
import '../../css/r/rgvk_601g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e11cv8b-r"/><path class="rgvk_601g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:check-square-bold" {...props}></Icon>
