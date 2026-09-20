<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrut08e3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrut08e3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:point-of-interest" {...props}></Icon>
