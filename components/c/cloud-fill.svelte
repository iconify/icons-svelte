<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5h25bq-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r5h25bq-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-fill" {...props}></Icon>
