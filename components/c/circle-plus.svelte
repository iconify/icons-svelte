<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd_1z1b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qd_1z1b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:circle-plus" {...props}></Icon>
