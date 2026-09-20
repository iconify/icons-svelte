<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erxn25bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":32};
const content = `<path class="erxn25bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nova-aws" {...props}></Icon>
