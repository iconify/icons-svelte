<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc5ahzv7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc5ahzv7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:blessing-line" {...props}></Icon>
