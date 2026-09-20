<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr0xqpt6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sr0xqpt6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-zoom-in-bold" {...props}></Icon>
