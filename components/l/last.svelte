<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3z5x8z7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="m3z5x8z7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:last" {...props}></Icon>
