<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt893gged.css';
import '../../css/e/eg39dacou.css';
import '../../css/f/fd1dolbaw.css';
import '../../css/m/m9u7wsbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gt893gged"/><path class="eg39dacou"/><path class="fd1dolbaw"/><path class="m9u7wsbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:clock7oclock" {...props}></Icon>
