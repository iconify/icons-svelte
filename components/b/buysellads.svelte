<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3ooak9tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="z3ooak9tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:buysellads" {...props}></Icon>
