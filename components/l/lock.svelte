<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxsvi7bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fxsvi7bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:lock" {...props}></Icon>
