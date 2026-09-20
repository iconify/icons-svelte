<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zev9aeikb.css';
import '../../css/v/vprbqcbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zev9aeikb"/><path class="vprbqcbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freshrss-dark" {...props}></Icon>
