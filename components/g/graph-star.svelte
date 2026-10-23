<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beosw2bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beosw2bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:graph-star" {...props}></Icon>
