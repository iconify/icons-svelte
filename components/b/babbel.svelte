<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4_xc7txx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":104.5,"height":68};
const content = `<path clip-rule="evenodd" class="o4_xc7txx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:babbel" {...props}></Icon>
