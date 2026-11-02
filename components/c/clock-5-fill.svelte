<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks7hnbbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks7hnbbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-5-fill" {...props}></Icon>
