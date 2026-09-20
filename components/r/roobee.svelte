<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5c4dtb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5c4dtb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:roobee" {...props}></Icon>
