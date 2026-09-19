<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psdg_7nuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psdg_7nuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-alert" {...props}></Icon>
