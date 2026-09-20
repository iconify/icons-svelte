<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5wkk8box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5wkk8box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-lkr" {...props}></Icon>
