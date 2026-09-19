<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obw0lbcts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="obw0lbcts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:link-external" {...props}></Icon>
