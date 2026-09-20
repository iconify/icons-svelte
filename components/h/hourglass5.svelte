<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh53vfb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="eh53vfb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:hourglass5" {...props}></Icon>
