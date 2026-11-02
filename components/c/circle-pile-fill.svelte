<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se4p66b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se4p66b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-pile-fill" {...props}></Icon>
