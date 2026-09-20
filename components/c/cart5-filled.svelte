<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b34_7zbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b34_7zbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cart5-filled" {...props}></Icon>
