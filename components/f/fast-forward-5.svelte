<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdqf4i_7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdqf4i_7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fast-forward-5" {...props}></Icon>
