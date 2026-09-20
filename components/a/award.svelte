<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4q40vp-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4q40vp-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:award" {...props}></Icon>
