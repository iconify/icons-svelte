<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sma2sc7pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sma2sc7pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bolt-slash" {...props}></Icon>
