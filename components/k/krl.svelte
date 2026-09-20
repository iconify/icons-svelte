<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq403ub1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq403ub1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:krl" {...props}></Icon>
