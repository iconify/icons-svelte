<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0arro94y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o0arro94y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:hackerrank" {...props}></Icon>
