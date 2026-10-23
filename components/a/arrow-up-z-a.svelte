<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyjc752ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyjc752ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-z-a" {...props}></Icon>
