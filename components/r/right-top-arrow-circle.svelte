<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyzmj84gk.css';
import '../../css/r/rrzjp2boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyzmj84gk"/><path class="rrzjp2boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:right-top-arrow-circle" {...props}></Icon>
