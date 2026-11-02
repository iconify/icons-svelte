<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3r4y_b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3r4y_b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:banknote-arrow-up-fill" {...props}></Icon>
