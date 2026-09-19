<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3zsrnb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3zsrnb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bullhorn-solid" {...props}></Icon>
