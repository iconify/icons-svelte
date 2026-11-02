<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9wdh4ajt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9wdh4ajt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-info-line" {...props}></Icon>
