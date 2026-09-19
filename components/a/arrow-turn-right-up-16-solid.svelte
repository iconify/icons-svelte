<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz778umpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rz778umpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-right-up-16-solid" {...props}></Icon>
