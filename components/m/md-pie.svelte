<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvklctb1s.css';
import '../../css/h/hck-_bb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xvklctb1s"/><path class="hck-_bb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-pie" {...props}></Icon>
