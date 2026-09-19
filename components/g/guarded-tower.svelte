<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-l5kbc7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w-l5kbc7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:guarded-tower" {...props}></Icon>
