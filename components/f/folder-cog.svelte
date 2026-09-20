<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul7_2-b5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul7_2-b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:folder-cog" {...props}></Icon>
