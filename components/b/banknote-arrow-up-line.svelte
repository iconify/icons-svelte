<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swqtet91a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swqtet91a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:banknote-arrow-up-line" {...props}></Icon>
