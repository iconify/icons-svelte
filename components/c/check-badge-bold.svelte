<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q482qm2fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="q482qm2fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:check-badge-bold" {...props}></Icon>
