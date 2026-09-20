<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1e8wfblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i1e8wfblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:envelope-open-outline" {...props}></Icon>
