<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i70y1sbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i70y1sbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:igdb" {...props}></Icon>
