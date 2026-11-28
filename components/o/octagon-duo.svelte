<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slknnlbbl.css';
import '../../css/s/s8ywqlbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary slknnlbbl"/><path class="primary s8ywqlbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:octagon-duo" {...props}></Icon>
