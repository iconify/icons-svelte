<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7pk1pbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7pk1pbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:flask-conical-off" {...props}></Icon>
