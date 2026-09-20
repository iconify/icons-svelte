<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frr0t2b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frr0t2b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-sharp-fill" {...props}></Icon>
