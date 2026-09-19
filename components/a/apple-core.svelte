<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdlk1kkcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bdlk1kkcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:apple-core" {...props}></Icon>
