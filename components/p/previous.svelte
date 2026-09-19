<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjd3gbc5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tjd3gbc5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:previous" {...props}></Icon>
