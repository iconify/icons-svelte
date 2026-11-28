<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqrj7tboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqrj7tboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:app-window-frown-solid" {...props}></Icon>
