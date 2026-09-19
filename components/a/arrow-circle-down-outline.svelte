<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt4kxjb1o.css';
import '../../css/w/wckr9kb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt4kxjb1o"/><path class="wckr9kb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-circle-down-outline" {...props}></Icon>
