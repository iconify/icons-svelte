<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go0c73cns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go0c73cns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:laptop-minimal-check-line" {...props}></Icon>
