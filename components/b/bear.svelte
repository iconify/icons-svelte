<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0vz-tbdb.css';
import '../../css/h/h5q9tn6hy.css';
import '../../css/r/riktqubqo.css';
import '../../css/z/zrbvzsbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b0vz-tbdb"/><path class="h5q9tn6hy"/><path class="riktqubqo"/><path class="zrbvzsbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:bear" {...props}></Icon>
