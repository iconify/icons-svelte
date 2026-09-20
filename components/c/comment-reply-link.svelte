<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u08k002sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="u08k002sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:comment-reply-link" {...props}></Icon>
