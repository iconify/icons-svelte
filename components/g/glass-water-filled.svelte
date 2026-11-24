<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojjtxm8cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ojjtxm8cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:glass-water-filled" {...props}></Icon>
