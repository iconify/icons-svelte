<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fix953b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fix953b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:location-blank-filled" {...props}></Icon>
