<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odlcg8hjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odlcg8hjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:list-letters" {...props}></Icon>
