<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggbfl18zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggbfl18zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-forward-outline" {...props}></Icon>
