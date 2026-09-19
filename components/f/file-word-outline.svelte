<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq8y1_y2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq8y1_y2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-word-outline" {...props}></Icon>
