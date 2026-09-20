<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttw1ccb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttw1ccb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:barbell-line" {...props}></Icon>
