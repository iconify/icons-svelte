<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gahg-u41y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gahg-u41y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:facebook-fill-24" {...props}></Icon>
