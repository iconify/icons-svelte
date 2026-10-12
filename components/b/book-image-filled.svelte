<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6tj1xb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6tj1xb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-image-filled" {...props}></Icon>
