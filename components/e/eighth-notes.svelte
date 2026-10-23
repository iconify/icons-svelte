<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc7ry0b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc7ry0b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:eighth-notes" {...props}></Icon>
