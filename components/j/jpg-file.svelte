<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrv-d9f8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xrv-d9f8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:jpg-file" {...props}></Icon>
