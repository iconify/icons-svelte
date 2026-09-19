<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hffe1tbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hffe1tbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:light-bulb" {...props}></Icon>
