<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mulb_7wla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mulb_7wla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-check-filled" {...props}></Icon>
