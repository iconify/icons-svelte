<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt33t8g3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dt33t8g3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:artificial-intelligence" {...props}></Icon>
