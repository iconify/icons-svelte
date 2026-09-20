<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emu7ok8id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emu7ok8id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:labor-hands-action-bold" {...props}></Icon>
