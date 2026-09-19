<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8fci18xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8fci18xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:comment-x" {...props}></Icon>
