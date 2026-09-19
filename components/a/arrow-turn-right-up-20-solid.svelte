<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itdsf40ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="itdsf40ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-right-up-20-solid" {...props}></Icon>
