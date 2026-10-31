<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu-yry1nz.css';
import '../../css/g/go5cygdbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tu-yry1nz"/><path clip-rule="evenodd" class="go5cygdbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-letter-r-filled" {...props}></Icon>
