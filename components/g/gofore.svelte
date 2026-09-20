<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9okqcc0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g9okqcc0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:gofore" {...props}></Icon>
