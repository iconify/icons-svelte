<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylgdlzb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylgdlzb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openverse" {...props}></Icon>
