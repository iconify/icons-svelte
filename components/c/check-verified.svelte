<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj25fl2bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj25fl2bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:check-verified" {...props}></Icon>
