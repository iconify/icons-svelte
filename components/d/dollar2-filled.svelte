<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy0ajee7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jy0ajee7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:dollar2-filled" {...props}></Icon>
