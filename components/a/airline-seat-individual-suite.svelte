<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fehcr6bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="fehcr6bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:airline-seat-individual-suite" {...props}></Icon>
