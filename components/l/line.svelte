<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x68q403fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x68q403fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:line" {...props}></Icon>
