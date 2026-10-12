<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8or5jvtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i8or5jvtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-euro-filled" {...props}></Icon>
