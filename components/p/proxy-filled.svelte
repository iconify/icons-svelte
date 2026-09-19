<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_94i1bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_94i1bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:proxy-filled" {...props}></Icon>
