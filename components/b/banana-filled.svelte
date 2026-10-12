<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6hxx9b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q6hxx9b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:banana-filled" {...props}></Icon>
