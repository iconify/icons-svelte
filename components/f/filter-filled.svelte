<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic74sqb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ic74sqb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:filter-filled" {...props}></Icon>
