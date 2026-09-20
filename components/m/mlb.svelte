<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izg9xkbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izg9xkbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mlb" {...props}></Icon>
