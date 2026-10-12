<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg1mtqeek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg1mtqeek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-pull-request-draft-filled" {...props}></Icon>
