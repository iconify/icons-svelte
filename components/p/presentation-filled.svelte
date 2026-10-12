<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff17ze2qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff17ze2qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:presentation-filled" {...props}></Icon>
