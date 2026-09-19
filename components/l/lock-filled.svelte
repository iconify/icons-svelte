<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugkyat6-v.css';
import '../../css/a/a1iy-fbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="ugkyat6-v"/><path clip-rule="evenodd" class="a1iy-fbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:lock-filled" {...props}></Icon>
