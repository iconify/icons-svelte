<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkrahr8qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dkrahr8qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:inbox-tray-2-solid" {...props}></Icon>
