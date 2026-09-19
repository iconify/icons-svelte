<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op64c1b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="op64c1b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-zip-solid" {...props}></Icon>
