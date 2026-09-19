<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf_yw3b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bf_yw3b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:2give" {...props}></Icon>
