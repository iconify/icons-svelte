<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9e90ybcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z9e90ybcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:disable-heart" {...props}></Icon>
