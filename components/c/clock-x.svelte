<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hazshzbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hazshzbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-x" {...props}></Icon>
