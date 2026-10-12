<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr8bbzbli.css';
import '../../css/l/lo4g9ospx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cr8bbzbli"/><path class="lo4g9ospx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cake-filled" {...props}></Icon>
