<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onup9ubsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onup9ubsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-russian-ruble-line" {...props}></Icon>
