<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc36aob7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc36aob7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-medical" {...props}></Icon>
