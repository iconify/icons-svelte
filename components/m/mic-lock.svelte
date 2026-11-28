<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl4zcvbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl4zcvbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mic-lock" {...props}></Icon>
