<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfsrp3blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfsrp3blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:casino-lucky-7-bold" {...props}></Icon>
