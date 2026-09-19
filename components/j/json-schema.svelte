<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxygdpu6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xxygdpu6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:json-schema" {...props}></Icon>
