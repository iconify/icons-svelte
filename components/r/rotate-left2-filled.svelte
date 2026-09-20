<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q75n7ib4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q75n7ib4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:rotate-left2-filled" {...props}></Icon>
