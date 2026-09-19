<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca-yr3bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ca-yr3bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlen" {...props}></Icon>
