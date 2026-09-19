<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z34kj1bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z34kj1bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:check-circle-solid" {...props}></Icon>
