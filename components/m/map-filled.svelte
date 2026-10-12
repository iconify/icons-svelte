<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8cu1vnkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8cu1vnkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-filled" {...props}></Icon>
