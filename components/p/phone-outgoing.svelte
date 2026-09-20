<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw_8mpbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw_8mpbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:phone-outgoing" {...props}></Icon>
