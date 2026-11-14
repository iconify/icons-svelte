<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je7-rtbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je7-rtbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:marker-cluster" {...props}></Icon>
