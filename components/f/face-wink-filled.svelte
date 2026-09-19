<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8uihsn-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z8uihsn-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:face-wink-filled" {...props}></Icon>
