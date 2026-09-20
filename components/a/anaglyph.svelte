<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu4vl3-ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="eu4vl3-ko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:anaglyph" {...props}></Icon>
