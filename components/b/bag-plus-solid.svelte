<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkch5_a1m.css';
import '../../css/j/j5118ebqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gkch5_a1m"/><path clip-rule="evenodd" class="j5118ebqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bag-plus-solid" {...props}></Icon>
