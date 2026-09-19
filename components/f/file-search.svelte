<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgkztrb3w.css';
import '../../css/z/ze7mxibna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgkztrb3w"/><path class="ze7mxibna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-search" {...props}></Icon>
