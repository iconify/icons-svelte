<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz4a96jsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nz4a96jsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:creative-commons-filled" {...props}></Icon>
