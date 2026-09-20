<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldnzu235l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ldnzu235l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:optician-11" {...props}></Icon>
