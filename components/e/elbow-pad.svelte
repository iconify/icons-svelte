<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wksmk7i5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wksmk7i5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:elbow-pad" {...props}></Icon>
