<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv0jxbc3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv0jxbc3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:car-4" {...props}></Icon>
