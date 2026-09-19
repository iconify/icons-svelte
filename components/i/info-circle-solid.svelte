<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g57a8jusd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g57a8jusd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:info-circle-solid" {...props}></Icon>
