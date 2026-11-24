<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayvld6ova.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ayvld6ova"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flower-2-filled" {...props}></Icon>
