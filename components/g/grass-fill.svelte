<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p03g2jbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p03g2jbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grass-fill" {...props}></Icon>
