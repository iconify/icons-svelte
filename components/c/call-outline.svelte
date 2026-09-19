<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj4wi1bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bj4wi1bgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:call-outline" {...props}></Icon>
