<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc8ekq55e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xc8ekq55e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-pdf-solid" {...props}></Icon>
