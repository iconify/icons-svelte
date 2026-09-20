<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se4exfb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="se4exfb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ban-sharp-fill" {...props}></Icon>
