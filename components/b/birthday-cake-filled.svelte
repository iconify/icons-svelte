<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ropm3r5qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ropm3r5qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:birthday-cake-filled" {...props}></Icon>
