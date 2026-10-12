<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efj21qvzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="efj21qvzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flower-filled" {...props}></Icon>
