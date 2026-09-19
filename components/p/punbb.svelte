<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f98h45baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f98h45baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:punbb" {...props}></Icon>
