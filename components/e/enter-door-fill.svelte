<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyjsuvhlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyjsuvhlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:enter-door-fill" {...props}></Icon>
