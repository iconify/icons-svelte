<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdpdfwpsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdpdfwpsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:home-2-filled" {...props}></Icon>
