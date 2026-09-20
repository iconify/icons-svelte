<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlpzi9wwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rlpzi9wwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:asterisk-square-solid" {...props}></Icon>
