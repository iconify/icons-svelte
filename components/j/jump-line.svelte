<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya14x0ett.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya14x0ett"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:jump-line" {...props}></Icon>
