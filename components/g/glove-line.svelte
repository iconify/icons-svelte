<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr61dzb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr61dzb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:glove-line" {...props}></Icon>
