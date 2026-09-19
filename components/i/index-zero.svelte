<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylbdoee0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ylbdoee0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:index-zero" {...props}></Icon>
