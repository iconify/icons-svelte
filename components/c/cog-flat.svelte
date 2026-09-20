<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdje1zcva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pdje1zcva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:cog-flat" {...props}></Icon>
