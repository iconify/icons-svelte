<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtakozb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rtakozb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:options" {...props}></Icon>
