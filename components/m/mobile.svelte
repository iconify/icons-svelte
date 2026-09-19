<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-8zpob_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-8zpob_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:mobile" {...props}></Icon>
