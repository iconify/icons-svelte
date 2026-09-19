<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anms5nb2o.css';
import '../../css/c/c9e9qbbyb.css';
import '../../css/h/hbq5upbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="anms5nb2o"/><path class="c9e9qbbyb"/><path class="hbq5upbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mic-off-circle-outline" {...props}></Icon>
