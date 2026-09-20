<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfubofbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sfubofbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:check-circle-fill-16" {...props}></Icon>
