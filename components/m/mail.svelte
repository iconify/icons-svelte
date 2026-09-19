<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sly2_52gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sly2_52gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:mail" {...props}></Icon>
