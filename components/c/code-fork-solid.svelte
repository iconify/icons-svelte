<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3mevab6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f3mevab6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:code-fork-solid" {...props}></Icon>
