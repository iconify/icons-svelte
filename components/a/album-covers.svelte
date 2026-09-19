<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w87quob4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w87quob4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:album-covers" {...props}></Icon>
