<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe5_628xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fe5_628xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-fill" {...props}></Icon>
