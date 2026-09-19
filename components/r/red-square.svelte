<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azp_fmbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="azp_fmbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:red-square" {...props}></Icon>
