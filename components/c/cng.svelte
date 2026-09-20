<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woae-0z3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woae-0z3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cng" {...props}></Icon>
