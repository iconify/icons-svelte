<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwoki8b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hwoki8b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:chevron-down-round" {...props}></Icon>
