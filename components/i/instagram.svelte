<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izpldp4wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="izpldp4wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:instagram" {...props}></Icon>
