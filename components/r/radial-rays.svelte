<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r51ckzluf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r51ckzluf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:radial-rays" {...props}></Icon>
