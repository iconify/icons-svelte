<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2yjogvfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v2yjogvfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:inbox-tray-2-remix" {...props}></Icon>
