<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q30fo1bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q30fo1bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mask3-filled" {...props}></Icon>
