<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pepju5brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pepju5brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:lubuntu-logo-solid" {...props}></Icon>
