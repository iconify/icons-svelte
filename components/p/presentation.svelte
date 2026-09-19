<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awf1jackb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="awf1jackb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:presentation" {...props}></Icon>
