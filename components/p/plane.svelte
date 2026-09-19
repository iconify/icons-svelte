<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga5whqb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":718,"height":716};
const content = `<path class="ga5whqb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:plane" {...props}></Icon>
