<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq9w7bkbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="jq9w7bkbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:multipoint" {...props}></Icon>
