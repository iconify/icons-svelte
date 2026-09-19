<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-2gchbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m-2gchbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:car-fill-16" {...props}></Icon>
