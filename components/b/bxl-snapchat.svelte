<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otd0h-0ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otd0h-0ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-snapchat" {...props}></Icon>
