<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhp0hry1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vhp0hry1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:corner-up-left-duotone" {...props}></Icon>
