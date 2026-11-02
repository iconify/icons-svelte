<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1sk-pb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1sk-pb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:banknote-x-line" {...props}></Icon>
