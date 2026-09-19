<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei-d5jmkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ei-d5jmkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:clear-all" {...props}></Icon>
