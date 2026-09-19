<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0ule9boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0ule9boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pendant-being" {...props}></Icon>
