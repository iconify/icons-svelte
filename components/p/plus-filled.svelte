<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_dochtfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z_dochtfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:plus-filled" {...props}></Icon>
