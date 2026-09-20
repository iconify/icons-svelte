<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3va__60v.css';
import '../../css/r/r8hicpb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3va__60v"/><path class="r8hicpb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:file-download-fill" {...props}></Icon>
