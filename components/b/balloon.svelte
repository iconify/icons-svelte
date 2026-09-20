<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxh8aml4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bxh8aml4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:balloon" {...props}></Icon>
