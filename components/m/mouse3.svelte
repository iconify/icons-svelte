<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln6oktiqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ln6oktiqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:mouse3" {...props}></Icon>
