<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp6fq4atn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wp6fq4atn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:carrot-filled" {...props}></Icon>
