<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owt28_bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="owt28_bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery" {...props}></Icon>
