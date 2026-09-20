<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrm7coa1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qrm7coa1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:front-camera-remix" {...props}></Icon>
