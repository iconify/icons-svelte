<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6ubm4bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="v6ubm4bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:car" {...props}></Icon>
