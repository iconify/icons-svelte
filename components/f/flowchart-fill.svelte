<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnm5rqkpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hnm5rqkpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:flowchart-fill" {...props}></Icon>
