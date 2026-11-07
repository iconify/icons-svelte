<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1jlu27kk.css';
import '../../css/d/dnv52pbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1jlu27kk"/><path class="dnv52pbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-right-left-bold" {...props}></Icon>
