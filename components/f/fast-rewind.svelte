<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqvt6ac-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":376,"height":384};
const content = `<path class="cqvt6ac-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:fast-rewind" {...props}></Icon>
