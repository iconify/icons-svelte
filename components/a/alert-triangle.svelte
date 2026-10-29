<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g962xhd_j.css';
import '../../css/s/syrsg1b7q.css';
import '../../css/b/bgzw4_2lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g962xhd_j wm-k"/><path class="syrsg1b7q wm-k"/><path class="bgzw4_2lq wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:alert-triangle" {...props}></Icon>
