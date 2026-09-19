<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te_6-yblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="te_6-yblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fluxbb" {...props}></Icon>
