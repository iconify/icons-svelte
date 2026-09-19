<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqblwla6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1408};
const content = `<path class="hqblwla6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:check-square-o" {...props}></Icon>
