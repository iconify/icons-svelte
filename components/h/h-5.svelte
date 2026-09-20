<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8tubrm5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8tubrm5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:h-5" {...props}></Icon>
