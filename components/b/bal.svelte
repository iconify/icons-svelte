<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cirejz0cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cirejz0cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bal" {...props}></Icon>
