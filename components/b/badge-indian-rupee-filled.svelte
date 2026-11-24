<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8ats2-zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h8ats2-zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-indian-rupee-filled" {...props}></Icon>
