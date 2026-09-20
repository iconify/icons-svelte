<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljd3w-lru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ljd3w-lru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:italic-solid" {...props}></Icon>
