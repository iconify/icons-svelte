<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8dfpftnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e8dfpftnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pen" {...props}></Icon>
