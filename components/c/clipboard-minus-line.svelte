<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o07bh_d7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o07bh_d7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clipboard-minus-line" {...props}></Icon>
