<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knbckdkfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="knbckdkfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:art-text-above-swash-line" {...props}></Icon>
