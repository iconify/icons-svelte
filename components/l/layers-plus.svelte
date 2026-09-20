<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acctyuoef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acctyuoef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:layers-plus" {...props}></Icon>
