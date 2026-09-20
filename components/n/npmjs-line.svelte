<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8qeanb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8qeanb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:npmjs-line" {...props}></Icon>
