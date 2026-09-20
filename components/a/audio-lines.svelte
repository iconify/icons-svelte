<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa8tgxnep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa8tgxnep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:audio-lines" {...props}></Icon>
