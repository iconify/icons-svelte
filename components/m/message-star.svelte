<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6lfs7i_j.css';
import '../../css/n/n-t7iwbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6lfs7i_j"/><path class="n-t7iwbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-star" {...props}></Icon>
