<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4oluribo.css';
import '../../css/c/c112rwb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4oluribo"/><path class="c112rwb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:contrast-filled" {...props}></Icon>
