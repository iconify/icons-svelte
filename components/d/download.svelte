<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbtl-i_cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbtl-i_cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:download" {...props}></Icon>
