<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v42uykb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v42uykb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-alt-lines" {...props}></Icon>
