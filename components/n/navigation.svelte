<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt3a1iz-v.css';
import '../../css/h/huhyiebpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt3a1iz-v"/><path class="huhyiebpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:navigation" {...props}></Icon>
