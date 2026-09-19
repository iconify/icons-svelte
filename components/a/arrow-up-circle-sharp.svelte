<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmp9btkqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pmp9btkqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:arrow-up-circle-sharp" {...props}></Icon>
