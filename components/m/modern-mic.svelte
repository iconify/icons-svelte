<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gufucky0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gufucky0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:modern-mic" {...props}></Icon>
