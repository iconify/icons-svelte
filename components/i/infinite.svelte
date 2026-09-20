<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-90m7y5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="d-90m7y5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:infinite" {...props}></Icon>
