<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no4_6ljhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="no4_6ljhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:map2-filled" {...props}></Icon>
