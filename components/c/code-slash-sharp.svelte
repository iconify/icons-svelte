<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8b0e2b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8b0e2b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:code-slash-sharp" {...props}></Icon>
