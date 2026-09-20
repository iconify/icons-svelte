<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp0hrebwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp0hrebwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:network-strength-3" {...props}></Icon>
