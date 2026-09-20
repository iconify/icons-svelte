<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j511gbccg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j511gbccg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:dimond-light" {...props}></Icon>
