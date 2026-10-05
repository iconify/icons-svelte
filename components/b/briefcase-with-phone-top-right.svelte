<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyhjk8bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iyhjk8bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-phone-top-right" {...props}></Icon>
