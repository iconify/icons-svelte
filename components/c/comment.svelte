<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu6xx9mid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="wu6xx9mid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:comment" {...props}></Icon>
