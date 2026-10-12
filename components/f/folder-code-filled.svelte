<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obb4mh94a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="obb4mh94a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-code-filled" {...props}></Icon>
