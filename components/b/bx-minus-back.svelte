<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qygkojtyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qygkojtyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-minus-back" {...props}></Icon>
