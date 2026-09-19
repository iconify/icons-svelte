<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh3o1ob7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh3o1ob7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cigarette-filled" {...props}></Icon>
