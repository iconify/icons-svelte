<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to5yjxb9u.css';
import '../../css/f/fup3d72ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="to5yjxb9u"/><path class="fup3d72ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:7-zip" {...props}></Icon>
