<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn1rxobwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn1rxobwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down" {...props}></Icon>
