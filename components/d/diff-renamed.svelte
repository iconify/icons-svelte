<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxan0itcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jxan0itcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:diff-renamed" {...props}></Icon>
