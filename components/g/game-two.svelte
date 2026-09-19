<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_d9w8b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a_d9w8b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:game-two" {...props}></Icon>
