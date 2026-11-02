<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvdz7j8kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvdz7j8kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:registered-line" {...props}></Icon>
