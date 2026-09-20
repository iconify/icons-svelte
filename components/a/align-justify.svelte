<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrqjflbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrqjflbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:align-justify" {...props}></Icon>
