<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yseymk-7a.css';
import '../../css/l/lt60qtbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yseymk-7a"/><path class="lt60qtbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mongodb-dark" {...props}></Icon>
