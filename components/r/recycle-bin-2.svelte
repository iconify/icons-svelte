<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7-aj4bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g7-aj4bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:recycle-bin-2" {...props}></Icon>
