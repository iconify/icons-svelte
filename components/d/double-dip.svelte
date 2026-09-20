<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu1zxebkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cu1zxebkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:double-dip" {...props}></Icon>
