<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r--g3ebmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r--g3ebmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:message-circle-dashed-check" {...props}></Icon>
