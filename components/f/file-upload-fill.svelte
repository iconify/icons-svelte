<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7agr4acm.css';
import '../../css/r/r8hicpb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7agr4acm"/><path class="r8hicpb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:file-upload-fill" {...props}></Icon>
