<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z71j1ujex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z71j1ujex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hamburger-menu-bold" {...props}></Icon>
