<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq26mfbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq26mfbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-7-fill" {...props}></Icon>
