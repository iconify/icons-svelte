<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zct_xzbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zct_xzbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:gift-filled" {...props}></Icon>
