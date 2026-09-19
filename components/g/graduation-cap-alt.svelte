<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f54c3mm_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f54c3mm_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:graduation-cap-alt" {...props}></Icon>
