<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sypk8ebrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sypk8ebrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-left-down" {...props}></Icon>
