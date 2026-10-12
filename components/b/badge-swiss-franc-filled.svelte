<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-585ybje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r-585ybje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-swiss-franc-filled" {...props}></Icon>
