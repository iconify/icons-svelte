<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mijl2lbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mijl2lbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:archive-restore-filled" {...props}></Icon>
