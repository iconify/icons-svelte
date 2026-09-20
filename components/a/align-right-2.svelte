<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcc8neiip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcc8neiip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-right-2" {...props}></Icon>
