<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfop6ibib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dfop6ibib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flask-conical-filled" {...props}></Icon>
