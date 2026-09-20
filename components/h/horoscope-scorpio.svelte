<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g55zcebja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g55zcebja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:horoscope-scorpio" {...props}></Icon>
