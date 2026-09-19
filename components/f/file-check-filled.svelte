<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxnma7qwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxnma7qwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-check-filled" {...props}></Icon>
