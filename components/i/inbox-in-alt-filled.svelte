<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztd26o_pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ztd26o_pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:inbox-in-alt-filled" {...props}></Icon>
