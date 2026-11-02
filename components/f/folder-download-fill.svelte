<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi0206b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi0206b5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-download-fill" {...props}></Icon>
