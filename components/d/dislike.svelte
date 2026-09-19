<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7h1kbbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7h1kbbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:dislike" {...props}></Icon>
