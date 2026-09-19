<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s34di-i6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="s34di-i6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:child-reaching" {...props}></Icon>
