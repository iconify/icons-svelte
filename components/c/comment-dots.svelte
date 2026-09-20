<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpjz01dis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpjz01dis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:comment-dots" {...props}></Icon>
