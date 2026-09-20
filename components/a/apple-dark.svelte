<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6jy5bc9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":814,"height":1000};
const content = `<path class="z6jy5bc9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apple-dark" {...props}></Icon>
