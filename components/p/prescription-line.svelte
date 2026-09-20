<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt74kkb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt74kkb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:prescription-line" {...props}></Icon>
