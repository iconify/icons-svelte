<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg-wc6boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sg-wc6boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:link-external-16" {...props}></Icon>
