<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w576l3brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w576l3brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comments" {...props}></Icon>
