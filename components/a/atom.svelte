<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj4fp2z8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sj4fp2z8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:atom" {...props}></Icon>
