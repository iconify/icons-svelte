<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhpprfezv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhpprfezv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:apple-imac-2021" {...props}></Icon>
