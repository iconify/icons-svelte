<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqrcerxvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nqrcerxvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-stop-solid" {...props}></Icon>
