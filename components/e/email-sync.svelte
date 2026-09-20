<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r368m6s7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r368m6s7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-sync" {...props}></Icon>
