<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgdc1bbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgdc1bbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:megaphone" {...props}></Icon>
