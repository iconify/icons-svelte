<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp6yibc6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp6yibc6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:flip-h-alt" {...props}></Icon>
