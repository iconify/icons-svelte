<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk_-lhb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dk_-lhb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:health" {...props}></Icon>
