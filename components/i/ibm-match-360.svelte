<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okiwfbt0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="okiwfbt0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-match-360" {...props}></Icon>
