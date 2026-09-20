<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0lg5lb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0lg5lb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:check" {...props}></Icon>
