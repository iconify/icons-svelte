<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqapnsbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqapnsbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-right-03" {...props}></Icon>
