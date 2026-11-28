<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md_acy2pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md_acy2pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clock-play" {...props}></Icon>
