<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7d7rjbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h7d7rjbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:boxes-filled" {...props}></Icon>
