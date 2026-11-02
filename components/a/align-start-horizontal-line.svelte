<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6_k5bbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6_k5bbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-start-horizontal-line" {...props}></Icon>
