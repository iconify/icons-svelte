<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_i561bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":26};
const content = `<path class="y_i561bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-26" {...props}></Icon>
