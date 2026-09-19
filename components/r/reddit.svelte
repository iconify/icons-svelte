<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxckild9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="nxckild9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:reddit" {...props}></Icon>
