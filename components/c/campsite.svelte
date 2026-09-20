<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkp9x86_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pkp9x86_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:campsite" {...props}></Icon>
