<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7mj_5rde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g7mj_5rde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bus-solid" {...props}></Icon>
