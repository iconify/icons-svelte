<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-rl59bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x-rl59bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-cycle-fill-16" {...props}></Icon>
