<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgqu7mb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xgqu7mb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:play" {...props}></Icon>
