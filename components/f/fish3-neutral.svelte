<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl0k0gb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xl0k0gb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fish3-neutral" {...props}></Icon>
