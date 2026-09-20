<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utyq8365n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utyq8365n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-patreon" {...props}></Icon>
