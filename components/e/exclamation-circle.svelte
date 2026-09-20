<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfh1ikz9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bfh1ikz9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:exclamation-circle" {...props}></Icon>
