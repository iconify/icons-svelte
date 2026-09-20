<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp8-qrb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gp8-qrb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:go-bottom-16" {...props}></Icon>
