<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm5dordkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm5dordkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:navigation-x" {...props}></Icon>
