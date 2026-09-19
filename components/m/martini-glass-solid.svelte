<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pii91ccva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pii91ccva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:martini-glass-solid" {...props}></Icon>
