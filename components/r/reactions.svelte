<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afp0twpdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="afp0twpdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:reactions" {...props}></Icon>
