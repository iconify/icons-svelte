<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jacuf9bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jacuf9bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-up-left-16-solid" {...props}></Icon>
