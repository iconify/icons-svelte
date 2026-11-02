<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8p2reb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8p2reb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-equal-fill" {...props}></Icon>
