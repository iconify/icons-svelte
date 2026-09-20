<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmdh-7bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmdh-7bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bench-back" {...props}></Icon>
