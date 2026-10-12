<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt_t8dbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nt_t8dbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:can-filled" {...props}></Icon>
