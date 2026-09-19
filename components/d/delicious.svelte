<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxz2ub4zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fxz2ub4zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:delicious" {...props}></Icon>
