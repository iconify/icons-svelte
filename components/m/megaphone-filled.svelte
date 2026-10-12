<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npdvl2brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npdvl2brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:megaphone-filled" {...props}></Icon>
