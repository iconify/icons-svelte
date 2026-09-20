<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyuhq9bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pyuhq9bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:basket" {...props}></Icon>
