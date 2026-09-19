<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4y4hbm4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f4y4hbm4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-up-right-16-solid" {...props}></Icon>
