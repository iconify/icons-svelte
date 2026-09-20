<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gthq0-bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="gthq0-bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:key-f" {...props}></Icon>
