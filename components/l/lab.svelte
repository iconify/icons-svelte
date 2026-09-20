<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owgrvf72e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="owgrvf72e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:lab" {...props}></Icon>
