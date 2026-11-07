<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1_y72bar.css';
import '../../css/b/b-ei31biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1_y72bar"/><path class="b-ei31biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playlist-2-bold-duotone" {...props}></Icon>
