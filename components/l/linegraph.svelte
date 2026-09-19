<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9wfist3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<path class="s9wfist3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:linegraph" {...props}></Icon>
