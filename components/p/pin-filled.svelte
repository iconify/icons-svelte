<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmmy88b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmmy88b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pin-filled" {...props}></Icon>
