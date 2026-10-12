<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j19sb1b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j19sb1b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-pull-request-closed-filled" {...props}></Icon>
