<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgm-rnbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cgm-rnbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:chevron-collapse-sharp" {...props}></Icon>
