<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icrxpc5-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="icrxpc5-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:connected" {...props}></Icon>
