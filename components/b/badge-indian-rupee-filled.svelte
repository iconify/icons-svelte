<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh-c-ubmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dh-c-ubmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-indian-rupee-filled" {...props}></Icon>
