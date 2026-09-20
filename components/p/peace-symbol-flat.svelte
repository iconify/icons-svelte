<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwh2s5nuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nwh2s5nuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:peace-symbol-flat" {...props}></Icon>
