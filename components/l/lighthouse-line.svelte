<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcivg91id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcivg91id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lighthouse-line" {...props}></Icon>
