<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm86fibta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nm86fibta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:new-file-solid" {...props}></Icon>
