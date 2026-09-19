<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l48585b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l48585b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:quote" {...props}></Icon>
