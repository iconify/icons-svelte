<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdqpy3b2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdqpy3b2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-taxi" {...props}></Icon>
