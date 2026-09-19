<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqynjwuib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aqynjwuib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:atom-core" {...props}></Icon>
