<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u09bqcbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u09bqcbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:alt-solid" {...props}></Icon>
