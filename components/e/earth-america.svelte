<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b890xw9rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b890xw9rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:earth-america" {...props}></Icon>
