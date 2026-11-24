<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wysaowb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wysaowb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-person-arms-spread-filled" {...props}></Icon>
