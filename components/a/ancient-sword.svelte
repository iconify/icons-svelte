<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6wpg2e-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x6wpg2e-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ancient-sword" {...props}></Icon>
