<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh1eqybkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":32};
const content = `<path class="lh1eqybkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nova-aws" {...props}></Icon>
