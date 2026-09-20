<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y47lqm_-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y47lqm_-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:boxing-glove-up" {...props}></Icon>
