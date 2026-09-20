<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv1m-94fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv1m-94fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:border-clear" {...props}></Icon>
