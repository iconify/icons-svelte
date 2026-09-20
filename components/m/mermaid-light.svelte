<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp6fmllkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":491,"height":491};
const content = `<path class="hp6fmllkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mermaid-light" {...props}></Icon>
