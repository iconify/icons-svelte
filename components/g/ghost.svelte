<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwjqeachp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwjqeachp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:ghost" {...props}></Icon>
