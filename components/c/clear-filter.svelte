<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oto0s4gdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oto0s4gdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:clear-filter" {...props}></Icon>
