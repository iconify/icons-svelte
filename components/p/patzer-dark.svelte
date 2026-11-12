<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd_7uwjfj.css';
import '../../css/h/h9qt_bcyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gd_7uwjfj"/><path class="h9qt_bcyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:patzer-dark" {...props}></Icon>
