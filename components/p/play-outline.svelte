<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga28a4bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga28a4bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:play-outline" {...props}></Icon>
