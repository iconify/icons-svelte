<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il7l4tb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":491,"height":491};
const content = `<path class="il7l4tb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mermaid-dark" {...props}></Icon>
