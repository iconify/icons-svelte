<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enx_use0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="enx_use0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bug-antivirus-shield-remix" {...props}></Icon>
