<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwi-3lbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwi-3lbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:postman" {...props}></Icon>
