<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efdukbclf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="efdukbclf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:list-selection" {...props}></Icon>
