<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2wpoel1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="r2wpoel1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:check-file" {...props}></Icon>
