<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbu-lrbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbu-lrbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-bottom-left" {...props}></Icon>
