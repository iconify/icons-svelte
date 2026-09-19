<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-03gibjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1408};
const content = `<path class="c-03gibjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:info" {...props}></Icon>
