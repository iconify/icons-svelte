<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulbs00b7h.css';
import '../../css/j/jvbg5sbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulbs00b7h"/><path clip-rule="evenodd" class="jvbg5sbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:confirmations-4-filled" {...props}></Icon>
