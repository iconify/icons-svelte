<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5cu15grx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d5cu15grx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:paintbrush-filled" {...props}></Icon>
