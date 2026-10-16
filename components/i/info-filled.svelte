<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/telbe8qah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="telbe8qah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:info-filled" {...props}></Icon>
