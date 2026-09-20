<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i05j46a2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i05j46a2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fahrenheit-fill" {...props}></Icon>
