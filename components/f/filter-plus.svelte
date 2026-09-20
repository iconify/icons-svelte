<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhjow86iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhjow86iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-plus" {...props}></Icon>
