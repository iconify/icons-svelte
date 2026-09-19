<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7jiv7qer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g7jiv7qer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:diff-multiple" {...props}></Icon>
