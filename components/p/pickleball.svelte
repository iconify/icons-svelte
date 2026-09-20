<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh1r0w9jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vh1r0w9jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:pickleball" {...props}></Icon>
