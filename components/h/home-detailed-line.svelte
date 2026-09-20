<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b19jhygnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b19jhygnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:home-detailed-line" {...props}></Icon>
