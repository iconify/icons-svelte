<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzsoemb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gzsoemb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:folder-plus-solid" {...props}></Icon>
