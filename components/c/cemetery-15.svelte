<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmti_bc9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wmti_bc9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:cemetery-15" {...props}></Icon>
