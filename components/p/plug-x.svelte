<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r37ut7cmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r37ut7cmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plug-x" {...props}></Icon>
