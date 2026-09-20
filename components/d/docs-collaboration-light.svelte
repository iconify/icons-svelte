<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jarn-80ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jarn-80ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docs-collaboration-light" {...props}></Icon>
