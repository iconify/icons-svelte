<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8mihqaoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8mihqaoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:adroll" {...props}></Icon>
