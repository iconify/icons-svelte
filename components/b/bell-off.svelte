<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqdbu0ewy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqdbu0ewy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bell-off" {...props}></Icon>
