<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puanc4qne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puanc4qne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:birthday-2-fill" {...props}></Icon>
