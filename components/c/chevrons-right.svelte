<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5e78hb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5e78hb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chevrons-right" {...props}></Icon>
