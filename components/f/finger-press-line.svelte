<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2kr22bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2kr22bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-press-line" {...props}></Icon>
