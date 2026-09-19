<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpoexrbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpoexrbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:diarrhea-24px" {...props}></Icon>
