<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbdsq-yur.css';
import '../../css/w/w22rijbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbdsq-yur"/><path class="w22rijbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pic-2-line" {...props}></Icon>
