<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geb6jiw3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geb6jiw3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-up-fill" {...props}></Icon>
