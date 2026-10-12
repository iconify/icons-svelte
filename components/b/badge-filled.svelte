<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giez_00ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="giez_00ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-filled" {...props}></Icon>
