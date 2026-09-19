<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1i1pzulb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l1i1pzulb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:check-circle-fill" {...props}></Icon>
