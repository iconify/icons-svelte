<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzheawb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uzheawb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrows-vertical" {...props}></Icon>
