<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyvsns5gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cyvsns5gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-left-outline" {...props}></Icon>
