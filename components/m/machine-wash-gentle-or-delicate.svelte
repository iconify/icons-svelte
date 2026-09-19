<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv-rjdbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":496};
const content = `<path class="xv-rjdbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:machine-wash-gentle-or-delicate" {...props}></Icon>
