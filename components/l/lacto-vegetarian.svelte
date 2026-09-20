<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlxnutbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlxnutbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lacto-vegetarian" {...props}></Icon>
