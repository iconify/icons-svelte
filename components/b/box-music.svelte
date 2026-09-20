<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhxs4nbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhxs4nbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-music" {...props}></Icon>
