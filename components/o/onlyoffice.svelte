<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvdaepbqt.css';
import '../../css/y/y1wes1v3b.css';
import '../../css/v/v9dfp9b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qvdaepbqt"/><path class="y1wes1v3b"/><path class="v9dfp9b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:onlyoffice" {...props}></Icon>
