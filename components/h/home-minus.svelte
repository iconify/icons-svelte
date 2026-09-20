<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i36_azmru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i36_azmru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:home-minus" {...props}></Icon>
