<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_o1j080n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":819,"height":727};
const content = `<path class="s_o1j080n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:cinnamon" {...props}></Icon>
