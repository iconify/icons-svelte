<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7_r7vb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j7_r7vb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:baggage-solid" {...props}></Icon>
