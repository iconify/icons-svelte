<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogq3q-bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ogq3q-bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pressure" {...props}></Icon>
