<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izau9c7zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izau9c7zz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:axis-bank" {...props}></Icon>
