<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj86u__cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oj86u__cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flamed-leaf" {...props}></Icon>
