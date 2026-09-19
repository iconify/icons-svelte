<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhhqvffwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhhqvffwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:navigation-01" {...props}></Icon>
