<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5-j6_bca.css';
import '../../css/s/svdy80z7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="d5-j6_bca"/><path class="svdy80z7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:circle-filled" {...props}></Icon>
