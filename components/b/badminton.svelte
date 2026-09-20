<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdp9ijb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fdp9ijb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:badminton" {...props}></Icon>
