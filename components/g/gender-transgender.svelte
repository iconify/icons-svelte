<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-uulzjes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-uulzjes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gender-transgender" {...props}></Icon>
