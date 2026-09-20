<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpp4bbb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpp4bbb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-2x3-sharp" {...props}></Icon>
