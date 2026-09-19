<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9e3p7bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y9e3p7bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fish4-sad" {...props}></Icon>
