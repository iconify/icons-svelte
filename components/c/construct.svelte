<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el07r1zqo.css';
import '../../css/o/oelx92bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="el07r1zqo"/><path class="oelx92bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:construct" {...props}></Icon>
