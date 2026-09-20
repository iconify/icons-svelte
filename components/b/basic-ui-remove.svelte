<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7_udfb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c7_udfb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-remove" {...props}></Icon>
