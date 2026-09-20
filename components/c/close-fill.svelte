<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7ir6kbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m7ir6kbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-fill" {...props}></Icon>
