<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwisqacpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mwisqacpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:message-check-filled" {...props}></Icon>
