<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgqhi0q5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgqhi0q5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:face-angry-filled" {...props}></Icon>
