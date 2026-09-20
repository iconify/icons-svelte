<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps35skh8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps35skh8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rakuten" {...props}></Icon>
