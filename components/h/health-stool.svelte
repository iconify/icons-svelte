<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4b-ycgux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d4b-ycgux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-stool" {...props}></Icon>
