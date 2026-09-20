<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp83xac0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp83xac0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:file-text" {...props}></Icon>
