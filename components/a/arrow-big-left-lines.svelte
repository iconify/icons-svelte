<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz8fjpbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz8fjpbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-left-lines" {...props}></Icon>
