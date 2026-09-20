<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6vf3kbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s6vf3kbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pool-ladder" {...props}></Icon>
