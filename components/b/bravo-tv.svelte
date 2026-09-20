<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1ypqnbnq.css';
import '../../css/w/wjox9-bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":999,"height":755};
const content = `<path class="r1ypqnbnq"/><path class="wjox9-bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bravo-tv" {...props}></Icon>
