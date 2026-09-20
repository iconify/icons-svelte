<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-6yb6bfg.css';
import '../../css/x/xxr0q9bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-6yb6bfg"/><path class="xxr0q9bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:cache-24" {...props}></Icon>
