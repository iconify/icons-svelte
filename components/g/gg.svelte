<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oagrx1-ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1344};
const content = `<path class="oagrx1-ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:gg" {...props}></Icon>
