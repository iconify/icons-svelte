<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg6qipopk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="tg6qipopk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:quote-a-left" {...props}></Icon>
