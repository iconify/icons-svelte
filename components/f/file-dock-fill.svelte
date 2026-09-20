<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyiib6bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyiib6bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:file-dock-fill" {...props}></Icon>
