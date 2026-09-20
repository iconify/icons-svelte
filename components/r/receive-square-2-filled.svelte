<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7wongkhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n7wongkhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:receive-square-2-filled" {...props}></Icon>
