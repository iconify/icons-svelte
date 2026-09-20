<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5mtn7z9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5mtn7z9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:export" {...props}></Icon>
