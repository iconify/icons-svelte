<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh8pb8bip.css';
import '../../css/l/l19bqcctk.css';
import '../../css/c/cs433rzwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xh8pb8bip"/><path class="l19bqcctk"/><path class="cs433rzwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-plus-20" {...props}></Icon>
