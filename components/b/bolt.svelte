<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj50_i5oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj50_i5oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bolt" {...props}></Icon>
