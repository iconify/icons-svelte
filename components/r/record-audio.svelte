<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwuatl62v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwuatl62v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:record-audio" {...props}></Icon>
