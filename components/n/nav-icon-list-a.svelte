<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s189b_bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="s189b_bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:nav-icon-list-a" {...props}></Icon>
