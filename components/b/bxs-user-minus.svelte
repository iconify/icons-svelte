<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd6sfoi7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd6sfoi7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-user-minus" {...props}></Icon>
