<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-92gbb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-92gbb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:building-2" {...props}></Icon>
