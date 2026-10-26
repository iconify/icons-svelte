<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umyjuccpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":96};
const content = `<path class="umyjuccpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:n8n-dark" {...props}></Icon>
