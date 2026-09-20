<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2xq-t_kz.css';
import '../../css/j/j51j01l3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b2xq-t_kz"/><path class="j51j01l3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:manifest-dark" {...props}></Icon>
