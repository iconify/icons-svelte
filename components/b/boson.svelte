<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa8jhvbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xa8jhvbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:boson" {...props}></Icon>
