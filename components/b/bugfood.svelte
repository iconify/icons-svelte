<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f38yl6i_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f38yl6i_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bugfood" {...props}></Icon>
