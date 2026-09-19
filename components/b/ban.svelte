<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp767_blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp767_blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:ban" {...props}></Icon>
