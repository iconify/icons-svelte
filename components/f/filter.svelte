<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4y7i6zog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o4y7i6zog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:filter" {...props}></Icon>
