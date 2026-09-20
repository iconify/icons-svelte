<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofx5qsbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ofx5qsbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:batch-check-outline" {...props}></Icon>
