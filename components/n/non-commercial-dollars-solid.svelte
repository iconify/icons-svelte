<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbu37c04o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bbu37c04o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:non-commercial-dollars-solid" {...props}></Icon>
