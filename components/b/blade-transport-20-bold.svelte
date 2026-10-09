<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erstu9bfm.css';
import '../../css/z/zi8delbng.css';
import '../../css/s/sahdhwl_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="erstu9bfm"/><path class="zi8delbng"/><path class="sahdhwl_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blade-transport-20-bold" {...props}></Icon>
