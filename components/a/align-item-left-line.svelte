<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shjd7ebvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shjd7ebvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-item-left-line" {...props}></Icon>
