<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mny56ybxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mny56ybxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-code-filled" {...props}></Icon>
