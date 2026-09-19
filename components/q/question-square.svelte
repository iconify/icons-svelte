<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5oid4tww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="j5oid4tww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:question-square" {...props}></Icon>
