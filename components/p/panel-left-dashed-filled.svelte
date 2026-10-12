<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxjl0ubfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rxjl0ubfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-left-dashed-filled" {...props}></Icon>
