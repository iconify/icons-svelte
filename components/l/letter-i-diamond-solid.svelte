<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbq8g6v3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbq8g6v3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-i-diamond-solid" {...props}></Icon>
