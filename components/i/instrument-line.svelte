<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abgai4bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abgai4bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:instrument-line" {...props}></Icon>
