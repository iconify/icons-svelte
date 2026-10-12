<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moluqpgom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moluqpgom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pin-off-filled" {...props}></Icon>
