<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eha3nnb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eha3nnb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:dagger" {...props}></Icon>
