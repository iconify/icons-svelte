<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag3oe707j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ag3oe707j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-top-right-with-exclamation-point" {...props}></Icon>
