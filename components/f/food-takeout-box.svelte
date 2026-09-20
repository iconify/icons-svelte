<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttb5vlbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttb5vlbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:food-takeout-box" {...props}></Icon>
