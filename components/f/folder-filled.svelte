<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwoeg07yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwoeg07yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-filled" {...props}></Icon>
