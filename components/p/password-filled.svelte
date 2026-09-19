<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-fuf2bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-fuf2bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:password-filled" {...props}></Icon>
