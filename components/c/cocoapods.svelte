<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7yldg-yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7yldg-yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cocoapods" {...props}></Icon>
