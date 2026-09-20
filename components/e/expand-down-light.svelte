<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrj2iywqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrj2iywqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:expand-down-light" {...props}></Icon>
