<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsikgs9ig.css';
import '../../css/s/s12m7vb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsikgs9ig"/><path clip-rule="evenodd" class="s12m7vb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:layers-minimalistic-bold" {...props}></Icon>
