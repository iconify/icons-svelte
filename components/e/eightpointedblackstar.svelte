<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa7jezu9i.css';
import '../../css/h/hn7rx0huz.css';
import '../../css/z/zavg8fb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sa7jezu9i"/><path class="hn7rx0huz"/><path class="zavg8fb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:eightpointedblackstar" {...props}></Icon>
