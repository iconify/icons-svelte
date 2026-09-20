<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahw0mccqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ahw0mccqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:battery2" {...props}></Icon>
