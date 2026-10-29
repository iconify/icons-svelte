<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf_c2vbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf_c2vbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:infinity" {...props}></Icon>
