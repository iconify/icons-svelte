<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxmavubqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxmavubqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-transfer" {...props}></Icon>
