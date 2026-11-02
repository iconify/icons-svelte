<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fltz9vbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fltz9vbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paper-line" {...props}></Icon>
