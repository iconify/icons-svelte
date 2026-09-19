<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_dx56bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="s_dx56bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pill-outline" {...props}></Icon>
