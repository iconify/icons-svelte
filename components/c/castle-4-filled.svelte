<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf3wfqbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf3wfqbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:castle-4-filled" {...props}></Icon>
