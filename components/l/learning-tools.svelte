<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oea5h3b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oea5h3b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:learning-tools" {...props}></Icon>
