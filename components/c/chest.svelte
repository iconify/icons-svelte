<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsm4ve1hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nsm4ve1hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:chest" {...props}></Icon>
