<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx-_nwbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx-_nwbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hepsiemlak" {...props}></Icon>
