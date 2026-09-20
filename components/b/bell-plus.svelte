<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qov099bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qov099bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-plus" {...props}></Icon>
