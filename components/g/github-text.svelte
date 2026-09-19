<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvi49bcnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":924.464,"height":1000};
const content = `<path class="cvi49bcnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:github-text" {...props}></Icon>
