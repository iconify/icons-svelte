<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku--r4boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku--r4boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:countingworks-pro" {...props}></Icon>
