<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bixg4h3ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bixg4h3ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:laptop-filled" {...props}></Icon>
