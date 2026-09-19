<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2dnkcbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x2dnkcbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-flask" {...props}></Icon>
