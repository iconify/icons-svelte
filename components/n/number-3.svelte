<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5nykxe0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5nykxe0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:number-3" {...props}></Icon>
