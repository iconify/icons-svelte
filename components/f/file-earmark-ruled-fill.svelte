<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa98zrbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sa98zrbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-ruled-fill" {...props}></Icon>
