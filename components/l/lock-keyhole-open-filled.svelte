<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbx04m8qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbx04m8qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lock-keyhole-open-filled" {...props}></Icon>
