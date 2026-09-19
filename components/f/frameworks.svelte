<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp41u6b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp41u6b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:frameworks" {...props}></Icon>
