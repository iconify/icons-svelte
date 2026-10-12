<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy9pkxbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy9pkxbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:haze-filled" {...props}></Icon>
