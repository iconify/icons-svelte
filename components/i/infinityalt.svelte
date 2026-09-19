<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkr9aqb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":632};
const content = `<path class="mkr9aqb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:infinityalt" {...props}></Icon>
