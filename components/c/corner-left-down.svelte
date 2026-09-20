<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjo-xpz6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjo-xpz6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:corner-left-down" {...props}></Icon>
