<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq99pwd1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq99pwd1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-line-increasing" {...props}></Icon>
