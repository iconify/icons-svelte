<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-dsfdcip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-dsfdcip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:badge-check-solid" {...props}></Icon>
