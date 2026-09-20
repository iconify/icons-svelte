<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lebseq6rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lebseq6rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gitkraken" {...props}></Icon>
